<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2eom2boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e2eom2boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scanopy-dark" {...props}></Icon>
