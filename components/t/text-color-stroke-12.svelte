<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f89y2qbtf.css';
import '../../css/u/u1ez71txv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f89y2qbtf"/><path class="u1ez71txv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-color-stroke-12" {...props}></Icon>
