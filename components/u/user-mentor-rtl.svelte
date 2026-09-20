<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck8kczb8t.css';
import '../../css/c/c-tt48brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ck8kczb8t"/><circle class="c-tt48brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-mentor-rtl" {...props}></Icon>
