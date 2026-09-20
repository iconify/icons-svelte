<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7hgbdc0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f7hgbdc0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-lock" {...props}></Icon>
