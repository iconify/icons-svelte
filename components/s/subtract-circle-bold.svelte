<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7defpb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7defpb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:subtract-circle-bold" {...props}></Icon>
