<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py46mcb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":472};
const content = `<path class="py46mcb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:wand" {...props}></Icon>
