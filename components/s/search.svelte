<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi3dgx43l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mi3dgx43l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:search" {...props}></Icon>
