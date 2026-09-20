<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr_wgacjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sr_wgacjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:spotify-logo-block" {...props}></Icon>
