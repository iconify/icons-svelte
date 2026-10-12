<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk_0rpbzb.css';
import '../../css/r/r67ffobwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk_0rpbzb"/><path class="r67ffobwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticky-note-minus-filled" {...props}></Icon>
