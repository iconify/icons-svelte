<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id0t_9blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="id0t_9blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-off-fill-20" {...props}></Icon>
