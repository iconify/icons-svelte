<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu4hl8fso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu4hl8fso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:smartphone-solid" {...props}></Icon>
