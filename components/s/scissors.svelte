<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq6o3_x6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wq6o3_x6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:scissors" {...props}></Icon>
