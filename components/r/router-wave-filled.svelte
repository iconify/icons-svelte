<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_zq91b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_zq91b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:router-wave-filled" {...props}></Icon>
