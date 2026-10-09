<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa2v1ywbh.css';
import '../../css/r/rfg83443v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sa2v1ywbh"/><path class="rfg83443v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-plus-20" {...props}></Icon>
