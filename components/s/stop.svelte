<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3p10wblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f3p10wblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:stop" {...props}></Icon>
