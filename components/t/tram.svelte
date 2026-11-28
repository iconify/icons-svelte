<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cin4ccc9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cin4ccc9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tram" {...props}></Icon>
