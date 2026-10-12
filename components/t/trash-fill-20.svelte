<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5rglpbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m5rglpbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:trash-fill-20" {...props}></Icon>
