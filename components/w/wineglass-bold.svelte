<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucsituugr.css';
import '../../css/n/nfab9gbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucsituugr"/><path class="nfab9gbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wineglass-bold" {...props}></Icon>
