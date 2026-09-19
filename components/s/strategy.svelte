<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/go2hddcxj.css';
import '../../css/i/i5wjkl-nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":32};
const content = `<g class="cuyn6tgcc"><path class="go2hddcxj"/><path class="i5wjkl-nm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:strategy" {...props}></Icon>
