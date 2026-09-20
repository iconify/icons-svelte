<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-khtibpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s-khtibpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-fill-16" {...props}></Icon>
