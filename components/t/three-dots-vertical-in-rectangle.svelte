<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzgx5tmfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kzgx5tmfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-dots-vertical-in-rectangle" {...props}></Icon>
