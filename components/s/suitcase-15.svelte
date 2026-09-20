<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo9gk5brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eo9gk5brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:suitcase-15" {...props}></Icon>
