<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exq42-b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="exq42-b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:trash" {...props}></Icon>
