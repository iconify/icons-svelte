<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcch0_ecx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcch0_ecx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:route-sharp" {...props}></Icon>
