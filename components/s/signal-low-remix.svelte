<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj9wi1brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vj9wi1brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-low-remix" {...props}></Icon>
