<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq_b-mhof.css';
import '../../css/z/zj49idy7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq_b-mhof"/><path class="zj49idy7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:x-circle-24" {...props}></Icon>
