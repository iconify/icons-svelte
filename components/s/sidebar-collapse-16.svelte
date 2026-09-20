<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj57gablw.css';
import '../../css/z/zqhih1b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oj57gablw"/><path class="zqhih1b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sidebar-collapse-16" {...props}></Icon>
