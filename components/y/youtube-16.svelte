<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo63pfbjq.css';
import '../../css/w/weqsqjbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oo63pfbjq"/><path clip-rule="evenodd" class="weqsqjbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:youtube-16" {...props}></Icon>
