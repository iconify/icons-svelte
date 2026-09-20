<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qejjhz08i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qejjhz08i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wifi-full-outline" {...props}></Icon>
