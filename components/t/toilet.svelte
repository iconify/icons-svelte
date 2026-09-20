<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4glezq6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s4glezq6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:toilet" {...props}></Icon>
