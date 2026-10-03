<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqi269k2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqi269k2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:smart-camera" {...props}></Icon>
