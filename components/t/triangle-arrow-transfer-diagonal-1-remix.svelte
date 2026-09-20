<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrkadbbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rrkadbbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-arrow-transfer-diagonal-1-remix" {...props}></Icon>
