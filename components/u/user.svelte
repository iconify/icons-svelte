<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq9u21biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kq9u21biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:user" {...props}></Icon>
