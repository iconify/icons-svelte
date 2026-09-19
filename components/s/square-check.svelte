<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu_-_ib9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pu_-_ib9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:square-check" {...props}></Icon>
