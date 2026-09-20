<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2csmvb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2csmvb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zzz-off" {...props}></Icon>
