<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x30kqj6eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x30kqj6eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:snow-flake-flat" {...props}></Icon>
