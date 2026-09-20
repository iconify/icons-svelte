<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u82at58qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u82at58qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:template" {...props}></Icon>
