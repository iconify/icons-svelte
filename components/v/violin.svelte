<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqyth8bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqyth8bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:violin" {...props}></Icon>
