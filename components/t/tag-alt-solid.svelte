<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt0usqk2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kt0usqk2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tag-alt-solid" {...props}></Icon>
