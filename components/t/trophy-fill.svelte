<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-cms5byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i-cms5byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trophy-fill" {...props}></Icon>
