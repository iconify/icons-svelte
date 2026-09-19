<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5xul3dgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d5xul3dgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-interface" {...props}></Icon>
