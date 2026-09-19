<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddwf0vbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddwf0vbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:transfer" {...props}></Icon>
