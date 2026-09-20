<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhdlglbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhdlglbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:spotify-logo-solid" {...props}></Icon>
