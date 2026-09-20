<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd7e0lmvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pd7e0lmvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:share" {...props}></Icon>
