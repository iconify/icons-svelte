<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwwdpl1kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwwdpl1kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tyre-fill" {...props}></Icon>
