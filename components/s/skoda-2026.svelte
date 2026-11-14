<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/semet6bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="semet6bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:skoda-2026" {...props}></Icon>
