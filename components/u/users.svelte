<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q323selxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q323selxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:users" {...props}></Icon>
