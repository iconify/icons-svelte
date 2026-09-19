<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w758uv4jk.css';
import '../../css/t/t5r-27-dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w758uv4jk"/><path class="t5r-27-dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:skype" {...props}></Icon>
