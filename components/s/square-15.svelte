<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4bhkzb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l4bhkzb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:square-15" {...props}></Icon>
