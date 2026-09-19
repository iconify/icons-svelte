<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8n9p-9ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="x8n9p-9ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stampalt" {...props}></Icon>
