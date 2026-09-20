<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbxhj-o3i.css';
import '../../css/v/vbqfmsb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbxhj-o3i"/><path class="vbqfmsb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:undo" {...props}></Icon>
