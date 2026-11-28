<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfm3n-qmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfm3n-qmc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-split-horizontal-duotone" {...props}></Icon>
