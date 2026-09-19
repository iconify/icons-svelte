<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0je8-nta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="a0je8-nta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:users-gear" {...props}></Icon>
