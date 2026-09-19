<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-tphckfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-tphckfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:truck-clock-solid" {...props}></Icon>
