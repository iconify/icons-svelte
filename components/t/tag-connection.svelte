<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr1wtrjto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pr1wtrjto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-connection" {...props}></Icon>
