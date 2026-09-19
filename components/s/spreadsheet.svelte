<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os3mvyh4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="os3mvyh4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:spreadsheet" {...props}></Icon>
