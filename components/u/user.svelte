<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p69xj7f-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p69xj7f-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:user" {...props}></Icon>
