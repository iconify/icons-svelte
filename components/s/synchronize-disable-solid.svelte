<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1bzzkbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1bzzkbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:synchronize-disable-solid" {...props}></Icon>
