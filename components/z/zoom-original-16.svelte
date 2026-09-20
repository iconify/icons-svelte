<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orz0cib-a.css';
import '../../css/w/wm45_4p5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="orz0cib-a"/><path clip-rule="evenodd" class="wm45_4p5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:zoom-original-16" {...props}></Icon>
