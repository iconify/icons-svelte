<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kss_nj_le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kss_nj_le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sword-fill" {...props}></Icon>
