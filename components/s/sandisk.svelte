<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyioyubov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1534,"height":1225};
const content = `<path class="fyioyubov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sandisk" {...props}></Icon>
