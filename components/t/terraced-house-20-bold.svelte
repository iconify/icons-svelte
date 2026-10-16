<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4-5bmdtc.css';
import '../../css/e/ei-x7jbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w4-5bmdtc"/><path class="ei-x7jbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terraced-house-20-bold" {...props}></Icon>
