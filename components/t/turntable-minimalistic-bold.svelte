<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-fhkt0hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-fhkt0hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:turntable-minimalistic-bold" {...props}></Icon>
