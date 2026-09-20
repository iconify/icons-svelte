<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwe9ecw5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uwe9ecw5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sign-out-16" {...props}></Icon>
