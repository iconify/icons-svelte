<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7lppbbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q7lppbbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:syncwave-dark" {...props}></Icon>
