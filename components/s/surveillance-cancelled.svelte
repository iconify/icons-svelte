<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a84atto0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a84atto0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:surveillance-cancelled" {...props}></Icon>
