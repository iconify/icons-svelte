<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir1xtxwio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ir1xtxwio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tennis" {...props}></Icon>
