<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfp3bzb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfp3bzb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:smallgear" {...props}></Icon>
