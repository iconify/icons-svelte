<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3o2nkoei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3o2nkoei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:streaming-logo-solid" {...props}></Icon>
