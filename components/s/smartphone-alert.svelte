<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slkc-1j8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slkc-1j8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartphone-alert" {...props}></Icon>
