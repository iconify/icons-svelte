<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0ccpfbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o0ccpfbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spring-20" {...props}></Icon>
