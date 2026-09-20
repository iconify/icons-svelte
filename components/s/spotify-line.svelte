<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iymet6bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iymet6bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spotify-line" {...props}></Icon>
