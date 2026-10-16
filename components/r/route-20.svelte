<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2ephobok.css';
import '../../css/c/clgy_7biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p2ephobok"/><path class="clgy_7biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:route-20" {...props}></Icon>
