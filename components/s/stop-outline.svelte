<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/i/imnimkbei.css';
import '../../css/z/zqzy3hb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="to-5kdesz"><path class="imnimkbei"/><path class="zqzy3hb6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:stop-outline" {...props}></Icon>
