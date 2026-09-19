<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_93w0w3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_93w0w3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:yen-square-solid" {...props}></Icon>
