<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7enk3mab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":328,"height":512};
const content = `<path class="e7enk3mab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:user" {...props}></Icon>
