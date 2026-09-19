<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1ux52a_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1792};
const content = `<path class="r1ux52a_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:thermometer-4" {...props}></Icon>
