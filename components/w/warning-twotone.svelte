<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayfgg5nwl.css';
import '../../css/c/ccaa01b9p.css';
import '../../css/j/jej9crbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ayfgg5nwl"/><path class="ccaa01b9p"/><path class="jej9crbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:warning-twotone" {...props}></Icon>
