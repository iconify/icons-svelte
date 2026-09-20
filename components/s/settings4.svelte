<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_8uv7b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_8uv7b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:settings4" {...props}></Icon>
