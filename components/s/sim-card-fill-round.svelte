<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv20g440o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv20g440o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sim-card-fill-round" {...props}></Icon>
