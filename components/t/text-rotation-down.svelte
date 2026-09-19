<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_yn9fbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h_yn9fbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:text-rotation-down" {...props}></Icon>
