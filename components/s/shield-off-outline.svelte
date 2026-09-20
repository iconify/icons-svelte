<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1r-lp53y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1r-lp53y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-off-outline" {...props}></Icon>
