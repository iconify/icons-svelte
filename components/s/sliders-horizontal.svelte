<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7_2a2mjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7_2a2mjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sliders-horizontal" {...props}></Icon>
