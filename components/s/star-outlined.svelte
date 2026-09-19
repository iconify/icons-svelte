<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqk3295an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oqk3295an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:star-outlined" {...props}></Icon>
