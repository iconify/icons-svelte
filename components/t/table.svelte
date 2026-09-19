<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpeh4lb3t.css';
import '../../css/p/pan8axb2r.css';
import '../../css/k/kfb89rzgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="fpeh4lb3t"/><path class="pan8axb2r"/><path class="kfb89rzgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:table" {...props}></Icon>
