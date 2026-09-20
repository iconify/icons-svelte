<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5h87bmtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="g5h87bmtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-check-filled" {...props}></Icon>
