<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-_7epjlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-_7epjlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shower-line" {...props}></Icon>
