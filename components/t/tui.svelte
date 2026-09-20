<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc66l36zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc66l36zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tui" {...props}></Icon>
