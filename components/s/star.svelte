<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm3x0j_xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="rm3x0j_xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:star" {...props}></Icon>
