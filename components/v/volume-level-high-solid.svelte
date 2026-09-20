<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue143cbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ue143cbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:volume-level-high-solid" {...props}></Icon>
