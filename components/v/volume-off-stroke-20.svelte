<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyz7sxb6l.css';
import '../../css/o/os103abfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yyz7sxb6l"/><path class="os103abfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-off-stroke-20" {...props}></Icon>
