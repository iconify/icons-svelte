<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3wmdbiab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x3wmdbiab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rust" {...props}></Icon>
