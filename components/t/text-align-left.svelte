<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-edk1j6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-edk1j6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:text-align-left" {...props}></Icon>
