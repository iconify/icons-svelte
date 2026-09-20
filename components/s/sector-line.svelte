<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sftsmcbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sftsmcbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sector-line" {...props}></Icon>
