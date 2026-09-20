<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcst-z.css';
import '../../css/n/n5xegl.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-34.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcst-z"/><path class="n5xegl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-right-half-filled" {...props}></Icon>
