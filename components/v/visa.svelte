<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6bejhbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6bejhbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:visa" {...props}></Icon>
