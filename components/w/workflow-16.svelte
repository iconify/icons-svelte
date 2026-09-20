<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut0ox1teu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ut0ox1teu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:workflow-16" {...props}></Icon>
