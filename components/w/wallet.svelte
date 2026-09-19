<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/temcgjo4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="temcgjo4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:wallet" {...props}></Icon>
