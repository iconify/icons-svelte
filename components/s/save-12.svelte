<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlxv6j38h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="zlxv6j38h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:save-12" {...props}></Icon>
