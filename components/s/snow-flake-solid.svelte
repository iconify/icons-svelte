<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgl11-bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgl11-bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:snow-flake-solid" {...props}></Icon>
