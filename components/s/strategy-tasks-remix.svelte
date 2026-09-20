<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq9se5byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uq9se5byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:strategy-tasks-remix" {...props}></Icon>
