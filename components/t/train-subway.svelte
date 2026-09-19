<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o39d96b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="o39d96b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:train-subway" {...props}></Icon>
