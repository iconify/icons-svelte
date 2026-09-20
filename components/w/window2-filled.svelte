<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8r2gdb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8r2gdb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:window2-filled" {...props}></Icon>
