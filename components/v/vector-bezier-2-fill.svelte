<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy0li2w-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy0li2w-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vector-bezier-2-fill" {...props}></Icon>
