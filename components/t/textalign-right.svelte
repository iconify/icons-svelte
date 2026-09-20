<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtkf2kbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtkf2kbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-right" {...props}></Icon>
