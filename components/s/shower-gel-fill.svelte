<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i79vfgbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i79vfgbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shower-gel-fill" {...props}></Icon>
