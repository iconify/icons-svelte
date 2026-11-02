<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwt8cbcha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwt8cbcha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:underline-fill" {...props}></Icon>
