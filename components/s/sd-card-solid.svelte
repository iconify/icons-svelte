<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptuvc-bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptuvc-bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sd-card-solid" {...props}></Icon>
