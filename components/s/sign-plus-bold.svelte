<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc203_r0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc203_r0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-bold" {...props}></Icon>
