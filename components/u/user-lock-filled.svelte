<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcht8racb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jcht8racb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-lock-filled" {...props}></Icon>
