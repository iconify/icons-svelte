<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3gbiob9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k3gbiob9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:speed-dip" {...props}></Icon>
