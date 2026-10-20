<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq6amyqet.css';
import '../../css/y/yoyl5gbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lq6amyqet"/><path class="yoyl5gbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:search-sparkle-20" {...props}></Icon>
