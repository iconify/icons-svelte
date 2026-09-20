<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x43fonber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x43fonber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shield-half" {...props}></Icon>
