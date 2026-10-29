<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mun6vbc9f.css';
import '../../css/g/gs5m2mmri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mun6vbc9f wm-k"/><path class="gs5m2mmri wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:square-x" {...props}></Icon>
