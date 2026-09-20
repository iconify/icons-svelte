<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf2akq2kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf2akq2kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ship-off" {...props}></Icon>
