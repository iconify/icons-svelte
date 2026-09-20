<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe8fokbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xe8fokbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-level-low-remix" {...props}></Icon>
