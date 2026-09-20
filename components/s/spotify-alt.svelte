<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqjoz67jv.css';
import '../../css/g/gwcmzd5cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqjoz67jv"/><path clip-rule="evenodd" class="gwcmzd5cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spotify-alt" {...props}></Icon>
