<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xalkdwbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xalkdwbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:soft-drinks-bottle-1-bold" {...props}></Icon>
