<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt73-z00d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt73-z00d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:strikethrough" {...props}></Icon>
