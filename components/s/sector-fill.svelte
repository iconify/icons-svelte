<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvm18-ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvm18-ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sector-fill" {...props}></Icon>
