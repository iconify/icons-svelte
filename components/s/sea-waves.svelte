<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8tvrxfjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8tvrxfjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sea-waves" {...props}></Icon>
