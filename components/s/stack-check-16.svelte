<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu8w1z02t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cu8w1z02t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:stack-check-16" {...props}></Icon>
