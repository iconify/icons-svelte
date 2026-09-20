<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzvrqh3yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzvrqh3yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:world-fill" {...props}></Icon>
