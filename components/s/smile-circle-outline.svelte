<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8mxup0kb.css';
import '../../css/v/vu18-_bab.css';
import '../../css/l/lg9shfpyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8mxup0kb"/><path class="vu18-_bab"/><path class="lg9shfpyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smile-circle-outline" {...props}></Icon>
