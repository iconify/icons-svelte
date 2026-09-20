<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yenvxqbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yenvxqbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:scanner-bar-code" {...props}></Icon>
