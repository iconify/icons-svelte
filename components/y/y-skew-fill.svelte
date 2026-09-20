<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5e48gbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s5e48gbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:y-skew-fill" {...props}></Icon>
