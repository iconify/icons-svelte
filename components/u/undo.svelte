<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cint8ubeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="cint8ubeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:undo" {...props}></Icon>
