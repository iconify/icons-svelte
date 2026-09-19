<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3pg_fb6f.css';
import '../../css/z/zunt0gbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="r3pg_fb6f"/><path class="zunt0gbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:transgender-outline" {...props}></Icon>
