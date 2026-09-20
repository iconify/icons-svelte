<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbke60bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbke60bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:usdt" {...props}></Icon>
