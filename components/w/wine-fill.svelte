<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_d5kvhro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_d5kvhro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wine-fill" {...props}></Icon>
