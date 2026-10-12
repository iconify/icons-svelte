<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apx8esb2g.css';
import '../../css/q/qz-yjjbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="apx8esb2g"/><path class="qz-yjjbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whiteboard-20-bold" {...props}></Icon>
