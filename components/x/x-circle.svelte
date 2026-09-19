<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvx5yfbep.css';
import '../../css/t/t91s7oy2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hvx5yfbep"/><path class="t91s7oy2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:x-circle" {...props}></Icon>
