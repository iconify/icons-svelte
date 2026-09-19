<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz1pvbcft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tz1pvbcft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:untag" {...props}></Icon>
