<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca7cey2zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca7cey2zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:spool" {...props}></Icon>
