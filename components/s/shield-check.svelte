<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i95-prgfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i95-prgfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:shield-check" {...props}></Icon>
