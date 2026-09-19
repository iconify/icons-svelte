<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/payqtdb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="payqtdb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:swipe-up-gesture" {...props}></Icon>
