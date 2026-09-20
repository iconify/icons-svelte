<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hccwo5byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hccwo5byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:skull-2-solid" {...props}></Icon>
