<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r02e4qbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r02e4qbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-v" {...props}></Icon>
