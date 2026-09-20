<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9f9qcklb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9f9qcklb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sun-solid" {...props}></Icon>
