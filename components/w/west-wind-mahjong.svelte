<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdafhn1uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mdafhn1uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:west-wind-mahjong" {...props}></Icon>
