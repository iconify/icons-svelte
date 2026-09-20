<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzd4rrbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzd4rrbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-play-filled" {...props}></Icon>
