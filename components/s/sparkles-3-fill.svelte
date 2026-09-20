<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhae6cciv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhae6cciv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sparkles-3-fill" {...props}></Icon>
