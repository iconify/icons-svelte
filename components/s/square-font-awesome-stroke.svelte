<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf8ygpznr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wf8ygpznr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-font-awesome-stroke" {...props}></Icon>
