<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmc6b3kjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dmc6b3kjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:timer-zero-remix" {...props}></Icon>
