<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joxi-ub2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="joxi-ub2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-reading-filled" {...props}></Icon>
