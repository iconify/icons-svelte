<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5vato6fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="n5vato6fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:wheelchair-alt" {...props}></Icon>
