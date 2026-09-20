<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kao65-mts.css';
import '../../css/x/xah9mvbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kao65-mts"/><path class="xah9mvbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xrsh-dark" {...props}></Icon>
