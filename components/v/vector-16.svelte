<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gae6d5d6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gae6d5d6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:vector-16" {...props}></Icon>
