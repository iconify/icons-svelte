<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-v5tybll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t-v5tybll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sail-ship-remix" {...props}></Icon>
