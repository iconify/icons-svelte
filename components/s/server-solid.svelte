<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh6i10s1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh6i10s1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:server-solid" {...props}></Icon>
