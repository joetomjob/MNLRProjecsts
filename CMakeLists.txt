cmake_minimum_required(VERSION 3.7)
project(Newcode)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        baseConversion.h
        boolean.h
        endNetworkUtils.h
        endNW.c
        errorControl.h
        fwd_MPLRData.c
        fwd_MPLRDecapsulation.c
        fwdAlgorithm.c
        fwdAlgorithmHelper.h
        genEnvironment.h
        helloList.h
        helloM_List.c
        printPacketDetails.h
        send_MPLRCtrl.c
        send_MPLRData.c
        send_MPLREndNW.c
        sendAndFwd.h
        stringMessages.h
        tierList.h
        tierUtils.h
        updateEnvironment.c)

add_executable(Newcode ${SOURCE_FILES})