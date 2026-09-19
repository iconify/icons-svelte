<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_ka4sc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a_ka4sc6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:signal" {...props}></Icon>
