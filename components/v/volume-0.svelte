<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds3f65bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ds3f65bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:volume-0" {...props}></Icon>
