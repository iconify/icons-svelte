<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrp7z4j1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrp7z4j1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shipping-box-1-solid" {...props}></Icon>
