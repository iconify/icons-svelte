<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqs_8pbmm.css';
import '../../css/c/c-9yccowm.css';
import '../../css/c/cpqrj-bqc.css';
import '../../css/o/orezepfbe.css';
import '../../css/y/ygtv74bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qqs_8pbmm"/><path class="c-9yccowm"/><path class="cpqrj-bqc"/><path class="orezepfbe"/><path class="ygtv74bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tracker-alert-48-bold" {...props}></Icon>
