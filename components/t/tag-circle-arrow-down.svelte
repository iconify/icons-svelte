<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syvbss82p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="syvbss82p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-circle-arrow-down" {...props}></Icon>
