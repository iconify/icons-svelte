<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i168pb04v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="i168pb04v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rules" {...props}></Icon>
