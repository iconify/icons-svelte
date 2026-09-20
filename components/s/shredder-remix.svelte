<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1n9x_bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j1n9x_bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shredder-remix" {...props}></Icon>
