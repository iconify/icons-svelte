<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz74pvtjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz74pvtjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-fill-24" {...props}></Icon>
