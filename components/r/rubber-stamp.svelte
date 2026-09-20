<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u12i6ub3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u12i6ub3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rubber-stamp" {...props}></Icon>
