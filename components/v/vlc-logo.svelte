<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3z_smx1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3z_smx1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:vlc-logo" {...props}></Icon>
