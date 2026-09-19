<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-atscb1d.css';
import '../../css/f/flmcfydke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-atscb1d"/><path class="flmcfydke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:wallet-solid" {...props}></Icon>
