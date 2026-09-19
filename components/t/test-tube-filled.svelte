<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckad6q9jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ckad6q9jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:test-tube-filled" {...props}></Icon>
