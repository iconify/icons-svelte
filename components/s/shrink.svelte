<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggis7yklh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggis7yklh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shrink" {...props}></Icon>
