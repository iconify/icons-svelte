<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx2lb6epn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="bx2lb6epn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:today" {...props}></Icon>
