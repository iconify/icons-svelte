<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fubg32b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fubg32b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:surfboard-fill" {...props}></Icon>
