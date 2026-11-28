<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcn42sblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcn42sblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-check-solid" {...props}></Icon>
