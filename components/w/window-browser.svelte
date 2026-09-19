<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd5bjjydz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xd5bjjydz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:window-browser" {...props}></Icon>
