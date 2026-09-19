<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atcc8608c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="atcc8608c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:wordpress" {...props}></Icon>
