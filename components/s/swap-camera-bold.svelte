<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmy16fsgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmy16fsgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:swap-camera-bold" {...props}></Icon>
