<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utsibk09e.css';
import '../../css/v/vke_idboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utsibk09e"/><path class="vke_idboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:self-healing" {...props}></Icon>
