<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhdb-55mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zhdb-55mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:undo-16" {...props}></Icon>
