<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n154e6bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n154e6bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:three-bars-24" {...props}></Icon>
