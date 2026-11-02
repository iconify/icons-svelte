<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5-jrab_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5-jrab_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sun-2-fill" {...props}></Icon>
