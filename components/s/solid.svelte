<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbrkcx08y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbrkcx08y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:solid" {...props}></Icon>
