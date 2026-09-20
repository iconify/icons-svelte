<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv5_69tgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rv5_69tgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-level-low" {...props}></Icon>
