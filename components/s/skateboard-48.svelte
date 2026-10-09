<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zor6y16jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zor6y16jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skateboard-48" {...props}></Icon>
