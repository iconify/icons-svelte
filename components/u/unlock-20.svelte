<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prrieubjn.css';
import '../../css/b/blb62kxgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="prrieubjn"/><path class="blb62kxgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:unlock-20" {...props}></Icon>
