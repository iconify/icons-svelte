<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv8h0sugj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv8h0sugj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sliders-2-vertical" {...props}></Icon>
