<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ila0mqwnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ila0mqwnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sea-lion-and-question-mark" {...props}></Icon>
