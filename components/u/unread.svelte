<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1h9l5vao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u1h9l5vao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:unread" {...props}></Icon>
