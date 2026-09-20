<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my7a5ub9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="my7a5ub9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:stereo-16" {...props}></Icon>
