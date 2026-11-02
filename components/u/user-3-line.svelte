<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8l8vnb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8l8vnb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-3-line" {...props}></Icon>
