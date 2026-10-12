<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yellpjx9e.css';
import '../../css/l/l8r0bab9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yellpjx9e"/><path class="l8r0bab9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:warehouse-filled" {...props}></Icon>
