<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytg06bcnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ytg06bcnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:zoom-out" {...props}></Icon>
