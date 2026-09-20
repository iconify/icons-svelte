<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0kg0ccbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v0kg0ccbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:subtract-square-remix" {...props}></Icon>
