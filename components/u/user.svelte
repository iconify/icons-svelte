<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prxrvu5lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="prxrvu5lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:user" {...props}></Icon>
