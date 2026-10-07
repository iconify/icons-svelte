<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooaogza-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ooaogza-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:stack-slash-16" {...props}></Icon>
