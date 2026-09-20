<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwq6kdb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rwq6kdb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-tag" {...props}></Icon>
