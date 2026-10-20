<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grwem7bvz.css';
import '../../css/a/anr4_-b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="grwem7bvz"/><path class="anr4_-b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tab-key-20" {...props}></Icon>
