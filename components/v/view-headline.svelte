<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2yf0pbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2yf0pbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-headline" {...props}></Icon>
