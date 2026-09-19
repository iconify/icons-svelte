<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyok70tso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyok70tso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:tv-outline" {...props}></Icon>
