<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi3x8dbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fi3x8dbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:subtract-fill" {...props}></Icon>
