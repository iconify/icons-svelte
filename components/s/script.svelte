<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwhvnw36m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwhvnw36m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:script" {...props}></Icon>
