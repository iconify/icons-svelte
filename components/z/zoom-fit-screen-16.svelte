<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9snzwc9m.css';
import '../../css/m/moby6ptxx.css';
import '../../css/p/pvxq0hblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j9snzwc9m"/><path class="moby6ptxx"/><path class="pvxq0hblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:zoom-fit-screen-16" {...props}></Icon>
