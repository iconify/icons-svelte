<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn_rija9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tn_rija9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:streamplay-logo-solid" {...props}></Icon>
