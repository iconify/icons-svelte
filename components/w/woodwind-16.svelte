<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwszy3bem.css';
import '../../css/o/ovjr3gbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dwszy3bem"/><path class="ovjr3gbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:woodwind-16" {...props}></Icon>
