<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e59x_pbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e59x_pbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:yaki-dango" {...props}></Icon>
