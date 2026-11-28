<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxskyzbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxskyzbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square-arrow-up" {...props}></Icon>
