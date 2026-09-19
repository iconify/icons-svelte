<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on8zofbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="on8zofbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:tree" {...props}></Icon>
