<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsjdy5i_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsjdy5i_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-crown-outline" {...props}></Icon>
