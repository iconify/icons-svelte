<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/al79j7shr.css';
import '../../css/s/sjrp4tbnl.css';
import '../../css/t/tdtdzw8lk.css';
import '../../css/b/b2vvr6bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="al79j7shr"/><path class="sjrp4tbnl"/><path class="tdtdzw8lk"/><path class="b2vvr6bvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-4-line-duotone" {...props}></Icon>
