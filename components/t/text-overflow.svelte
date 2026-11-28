<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo0x7ob7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bo0x7ob7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-overflow" {...props}></Icon>
