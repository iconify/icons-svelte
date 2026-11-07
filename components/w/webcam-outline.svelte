<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnf6ldb9q.css';
import '../../css/z/zjftgfb_b.css';
import '../../css/c/c32p5b3tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnf6ldb9q"/><path class="zjftgfb_b"/><path clip-rule="evenodd" class="c32p5b3tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:webcam-outline" {...props}></Icon>
