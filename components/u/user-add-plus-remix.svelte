<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttu--1nke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ttu--1nke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-add-plus-remix" {...props}></Icon>
