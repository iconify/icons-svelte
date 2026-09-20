<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/watea3b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="watea3b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:symmetry-mirror-1-solid" {...props}></Icon>
