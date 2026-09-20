<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-wc5tbnn.css';
import '../../css/z/zj49idy7n.css';
import '../../css/p/psb8q1--l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-wc5tbnn"/><path class="zj49idy7n"/><path class="psb8q1--l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:smiley-24" {...props}></Icon>
