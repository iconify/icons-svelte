<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylpsw_5zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ylpsw_5zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:t-rex" {...props}></Icon>
