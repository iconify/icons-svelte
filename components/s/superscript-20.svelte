<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k50br_b8z.css';
import '../../css/t/t3e4vmwxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k50br_b8z"/><path class="t3e4vmwxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:superscript-20" {...props}></Icon>
