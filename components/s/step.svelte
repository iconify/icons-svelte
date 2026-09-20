<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff4d8cc3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ff4d8cc3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:step" {...props}></Icon>
