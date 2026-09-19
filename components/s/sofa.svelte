<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdz7ysb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1600};
const content = `<path class="tdz7ysb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sofa" {...props}></Icon>
