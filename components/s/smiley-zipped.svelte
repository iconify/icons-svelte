<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky8c2yxsy.css';
import '../../css/o/oy5x1vbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky8c2yxsy"/><path class="oy5x1vbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-zipped" {...props}></Icon>
