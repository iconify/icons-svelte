<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx1df9t7l.css';
import '../../css/c/cjnhv0ssg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1df9t7l"/><path class="cjnhv0ssg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:video-plus" {...props}></Icon>
