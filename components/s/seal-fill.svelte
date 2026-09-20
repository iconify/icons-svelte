<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuos9wz9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuos9wz9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:seal-fill" {...props}></Icon>
