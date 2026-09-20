<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qok2qrelu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qok2qrelu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:shazam-logo-solid" {...props}></Icon>
