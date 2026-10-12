<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1zk_dbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t1zk_dbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:slider-stroke-20" {...props}></Icon>
