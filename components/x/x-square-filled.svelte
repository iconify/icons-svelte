<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly1ve4w5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly1ve4w5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:x-square-filled" {...props}></Icon>
