<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5-r_jvrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5-r_jvrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vno" {...props}></Icon>
