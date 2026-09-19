<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psk9ti-eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psk9ti-eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wall-filled" {...props}></Icon>
