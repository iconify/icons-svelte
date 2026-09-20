<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfzq4k5vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vfzq4k5vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:water-tap-drinkable" {...props}></Icon>
