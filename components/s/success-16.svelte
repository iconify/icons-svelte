<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3b2z9bzs.css';
import '../../css/b/b2tyl1b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l3b2z9bzs"/><path clip-rule="evenodd" class="b2tyl1b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:success-16" {...props}></Icon>
