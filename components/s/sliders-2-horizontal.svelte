<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9fodabli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9fodabli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sliders-2-horizontal" {...props}></Icon>
