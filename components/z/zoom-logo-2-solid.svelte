<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1ah6mbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1ah6mbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:zoom-logo-2-solid" {...props}></Icon>
