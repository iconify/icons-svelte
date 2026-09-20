<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8s_krp1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8s_krp1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:typescript" {...props}></Icon>
