<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-pt2jepa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t-pt2jepa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:twitter-with-circle" {...props}></Icon>
