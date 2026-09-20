<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf_gkfb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf_gkfb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:uber" {...props}></Icon>
