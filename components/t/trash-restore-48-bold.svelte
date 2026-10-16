<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcwfyf16x.css';
import '../../css/l/lfgx0yqjl.css';
import '../../css/g/gvtf67ctb.css';
import '../../css/u/ucn402gew.css';
import '../../css/k/kuaiedclu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pcwfyf16x"/><path class="lfgx0yqjl"/><path class="gvtf67ctb"/><path class="ucn402gew"/><path class="kuaiedclu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trash-restore-48-bold" {...props}></Icon>
