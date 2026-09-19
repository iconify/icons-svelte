<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw2wlh8tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="fw2wlh8tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:toll" {...props}></Icon>
