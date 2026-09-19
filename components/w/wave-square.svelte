<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy69faciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="wy69faciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:wave-square" {...props}></Icon>
