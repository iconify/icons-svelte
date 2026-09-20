<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t57l3zbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t57l3zbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zotero-dark" {...props}></Icon>
