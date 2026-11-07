<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxe30nuth.css';
import '../../css/i/i5z920-bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxe30nuth"/><path class="i5z920-bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screencast-2-bold" {...props}></Icon>
