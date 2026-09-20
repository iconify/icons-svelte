<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr54odb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gr54odb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-standpipe-with-handle" {...props}></Icon>
