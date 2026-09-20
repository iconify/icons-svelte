<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud0_s6b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud0_s6b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:teamviewer" {...props}></Icon>
