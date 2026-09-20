<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek40-u_-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ek40-u_-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:workspace-desk-remix" {...props}></Icon>
