<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkhb168nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="fkhb168nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:steps-10" {...props}></Icon>
