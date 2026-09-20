<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg2r8uccd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg2r8uccd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-star" {...props}></Icon>
