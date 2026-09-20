<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg1oycbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg1oycbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-toggle" {...props}></Icon>
