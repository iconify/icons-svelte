<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp7cuw3ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp7cuw3ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:users-plus" {...props}></Icon>
