<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4hucmc0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="q4hucmc0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:waterfall-14" {...props}></Icon>
