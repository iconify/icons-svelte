<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bolmgdbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bolmgdbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:server-plus" {...props}></Icon>
