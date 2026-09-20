<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox3ovf3vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ox3ovf3vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:undo-1" {...props}></Icon>
