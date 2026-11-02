<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilai06dxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilai06dxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:squats-fill" {...props}></Icon>
