<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knxfsw6ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="knxfsw6ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:support" {...props}></Icon>
