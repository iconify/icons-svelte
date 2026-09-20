<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qth9flppj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qth9flppj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:scroll-up" {...props}></Icon>
