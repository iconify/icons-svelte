<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3ux1061w.css';
import '../../css/h/hupodmbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n3ux1061w"/><path class="hupodmbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-meter-20" {...props}></Icon>
