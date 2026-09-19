<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdee8uctf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gdee8uctf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:t-shirt" {...props}></Icon>
