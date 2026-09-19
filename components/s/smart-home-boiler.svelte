<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj7snwbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cj7snwbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:smart-home-boiler" {...props}></Icon>
