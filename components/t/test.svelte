<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0eiufg9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j0eiufg9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:test" {...props}></Icon>
