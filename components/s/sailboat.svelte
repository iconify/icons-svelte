<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ptjyb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o3ptjyb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sailboat" {...props}></Icon>
