<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kklwcubis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kklwcubis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:video-cinema" {...props}></Icon>
