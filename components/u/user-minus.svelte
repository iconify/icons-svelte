<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0-06wb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f0-06wb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-minus" {...props}></Icon>
