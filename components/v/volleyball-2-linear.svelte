<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvac8qbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvac8qbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volleyball-2-linear" {...props}></Icon>
