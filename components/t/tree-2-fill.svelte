<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5j3g4wfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5j3g4wfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tree-2-fill" {...props}></Icon>
