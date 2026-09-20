<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp37pgb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp37pgb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:substack-line" {...props}></Icon>
