<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkanzva6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="rkanzva6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tooth" {...props}></Icon>
