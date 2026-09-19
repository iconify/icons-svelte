<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lclbo1n2e.css';
import '../../css/h/helnm_mgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lclbo1n2e"/><path class="helnm_mgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:satellite-radar" {...props}></Icon>
