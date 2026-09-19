<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0qad_bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0qad_bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sine-wave" {...props}></Icon>
