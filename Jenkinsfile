#!/usr/bin/env groovy

@Library('etn-ipm2-jenkins') _

import params.CmakePipelineParams
CmakePipelineParams parameters = new CmakePipelineParams()
// run debug build without tests and memcheck
parameters.debugBuildRunTests = false
parameters.debugBuildRunMemcheck = false

etn_ipm2_build_and_tests_pipeline_cmake(parameters)
