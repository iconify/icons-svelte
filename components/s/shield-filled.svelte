<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1vlcdv9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a1vlcdv9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shield-filled" {...props}></Icon>
