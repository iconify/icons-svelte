<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8c3mobyr.css';
import '../../css/x/xlzl9rbag.css';
import '../../css/i/ie4e8tuss.css';
import '../../css/c/cgy2nq5hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d8c3mobyr"/><path class="xlzl9rbag"/><path class="ie4e8tuss"/><path class="cgy2nq5hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trash-20-bold" {...props}></Icon>
