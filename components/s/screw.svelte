<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9j5sz1kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="s9j5sz1kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:screw" {...props}></Icon>
