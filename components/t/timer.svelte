<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6fsplbwz.css';
import '../../css/l/l27lvlbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p6fsplbwz"/><path class="l27lvlbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:timer" {...props}></Icon>
