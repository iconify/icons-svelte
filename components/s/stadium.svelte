<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2-jwxbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":704,"height":960};
const content = `<path class="i2-jwxbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stadium" {...props}></Icon>
