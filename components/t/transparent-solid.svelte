<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm73ivbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm73ivbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:transparent-solid" {...props}></Icon>
