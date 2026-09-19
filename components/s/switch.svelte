<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct6z4mrtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct6z4mrtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:switch" {...props}></Icon>
