<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9nqfyckg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9nqfyckg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-16" {...props}></Icon>
