<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ist0xi34j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ist0xi34j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wifi-high-solid" {...props}></Icon>
