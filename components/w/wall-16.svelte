<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg1yx4lqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qg1yx4lqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wall-16" {...props}></Icon>
