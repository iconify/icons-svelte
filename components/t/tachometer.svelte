<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n57qnm33o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n57qnm33o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:tachometer" {...props}></Icon>
