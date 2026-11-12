<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e39b9hkls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e39b9hkls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whisparr-dark" {...props}></Icon>
