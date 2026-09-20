<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sug3ijbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sug3ijbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:watermill-15" {...props}></Icon>
