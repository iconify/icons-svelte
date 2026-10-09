<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrjlwqjtj.css';
import '../../css/a/au4v49w_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jrjlwqjtj"/><path class="au4v49w_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-high-20-bold" {...props}></Icon>
