<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxn3gdbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lxn3gdbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:save" {...props}></Icon>
