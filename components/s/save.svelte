<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_xno0bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_xno0bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:save" {...props}></Icon>
