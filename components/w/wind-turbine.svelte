<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh8yjs2_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh8yjs2_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wind-turbine" {...props}></Icon>
