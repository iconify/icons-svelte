<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt65e8btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt65e8btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sdk" {...props}></Icon>
