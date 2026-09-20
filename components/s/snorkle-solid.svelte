<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4qkq3-ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d4qkq3-ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:snorkle-solid" {...props}></Icon>
