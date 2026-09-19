<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2a315bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="p2a315bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vm-small" {...props}></Icon>
