<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9c-s5bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="q9c-s5bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:square-right" {...props}></Icon>
