<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9u0pyb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d9u0pyb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-strike-fill-20" {...props}></Icon>
