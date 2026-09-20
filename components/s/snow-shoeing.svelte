<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bilugcm1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="bilugcm1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:snow-shoeing" {...props}></Icon>
