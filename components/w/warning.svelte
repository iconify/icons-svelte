<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5v9h6b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":472};
const content = `<path class="e5v9h6b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:warning" {...props}></Icon>
