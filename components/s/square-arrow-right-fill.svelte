<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn7foybwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn7foybwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-right-fill" {...props}></Icon>
