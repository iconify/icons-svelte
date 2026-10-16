<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aajqmxblx.css';
import '../../css/l/lt_twkb4l.css';
import '../../css/p/p78aomkxz.css';
import '../../css/s/s0y6ktbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aajqmxblx"/><path class="lt_twkb4l"/><path class="p78aomkxz"/><path class="s0y6ktbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shed-20" {...props}></Icon>
