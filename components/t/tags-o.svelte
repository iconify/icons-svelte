<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5os33b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f5os33b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:tags-o" {...props}></Icon>
