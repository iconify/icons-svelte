<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spg4x5bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="spg4x5bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:skateboard-15" {...props}></Icon>
