<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftiz-zzun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftiz-zzun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:volume-low" {...props}></Icon>
