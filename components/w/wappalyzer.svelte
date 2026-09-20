<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f012qlbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f012qlbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wappalyzer" {...props}></Icon>
