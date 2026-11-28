<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjwd8jtei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjwd8jtei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smart-home-x" {...props}></Icon>
