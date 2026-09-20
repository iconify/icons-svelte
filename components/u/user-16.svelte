<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1u65mb1a.css';
import '../../css/e/e6siqkbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z1u65mb1a"/><path clip-rule="evenodd" class="e6siqkbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:user-16" {...props}></Icon>
