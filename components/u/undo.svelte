<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo0inq6hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo0inq6hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:undo" {...props}></Icon>
