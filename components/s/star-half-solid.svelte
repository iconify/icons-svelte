<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5wb2qbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5wb2qbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:star-half-solid" {...props}></Icon>
