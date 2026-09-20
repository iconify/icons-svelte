<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkm2jfh8m.css';
import '../../css/j/j2a76tb0l.css';
import '../../css/z/zurq1_b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkm2jfh8m"/><path class="j2a76tb0l"/><path class="zurq1_b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:security-gdpr-browser" {...props}></Icon>
