<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftzcaiq3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftzcaiq3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:router-gear" {...props}></Icon>
