<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asy189blx.css';
import '../../css/l/lveuvsb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asy189blx"/><path class="lveuvsb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:security-user-lock" {...props}></Icon>
