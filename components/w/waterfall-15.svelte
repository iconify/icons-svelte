<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5qn0db8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l5qn0db8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:waterfall-15" {...props}></Icon>
