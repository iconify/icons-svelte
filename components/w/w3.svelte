<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1efuxbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="n1efuxbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:w3" {...props}></Icon>
