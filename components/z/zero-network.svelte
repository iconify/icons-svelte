<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa41-ac5j.css';
import '../../css/m/mn-fhob2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa41-ac5j"/><path clip-rule="evenodd" class="mn-fhob2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zero-network" {...props}></Icon>
