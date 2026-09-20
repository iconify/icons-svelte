<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncp3p2b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncp3p2b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-left-round-linear" {...props}></Icon>
