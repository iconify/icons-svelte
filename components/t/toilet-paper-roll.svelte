<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpuhle7eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cpuhle7eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:toilet-paper-roll" {...props}></Icon>
