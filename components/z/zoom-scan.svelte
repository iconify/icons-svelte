<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-ia4j52q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-ia4j52q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-scan" {...props}></Icon>
