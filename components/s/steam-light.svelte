<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7zbigbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j7zbigbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:steam-light" {...props}></Icon>
