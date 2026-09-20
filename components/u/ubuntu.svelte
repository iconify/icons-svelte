<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfvl_quvy.css';
import '../../css/x/xwnqe-beb.css';
import '../../css/u/u4z7rnb1i.css';
import '../../css/c/clgcxl7va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xfvl_quvy"/><path clip-rule="evenodd" class="xwnqe-beb"/><path class="u4z7rnb1i"/><path class="clgcxl7va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ubuntu" {...props}></Icon>
