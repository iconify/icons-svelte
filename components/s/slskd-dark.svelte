<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkcr4nuis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkcr4nuis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:slskd-dark" {...props}></Icon>
