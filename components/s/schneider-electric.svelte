<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q12uogbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q12uogbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:schneider-electric" {...props}></Icon>
