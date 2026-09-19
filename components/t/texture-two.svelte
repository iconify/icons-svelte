<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbex2ksko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rbex2ksko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:texture-two" {...props}></Icon>
