<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd-ljgbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd-ljgbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zyte" {...props}></Icon>
