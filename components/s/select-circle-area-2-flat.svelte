<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky022pehc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ky022pehc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:select-circle-area-2-flat" {...props}></Icon>
