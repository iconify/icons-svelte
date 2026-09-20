<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-j79umnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c-j79umnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:telescope-fill-16" {...props}></Icon>
