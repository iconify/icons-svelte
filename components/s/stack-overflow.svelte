<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg6puob4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="fg6puob4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:stack-overflow" {...props}></Icon>
