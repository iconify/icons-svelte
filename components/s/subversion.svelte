<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbaj7zbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbaj7zbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:subversion" {...props}></Icon>
