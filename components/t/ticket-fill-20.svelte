<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzpemx0rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hzpemx0rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:ticket-fill-20" {...props}></Icon>
