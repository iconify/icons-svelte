<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hel45b33c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="hel45b33c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:stapler" {...props}></Icon>
