<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc-b3s.css';
import '../../css/c/chdxye.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-34.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc-b3s"/><path class="chdxye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-half-filled" {...props}></Icon>
