<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp2qei.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp2qei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:square-filled" {...props}></Icon>
