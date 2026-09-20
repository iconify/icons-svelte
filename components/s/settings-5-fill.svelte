<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnb6j5bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnb6j5bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-5-fill" {...props}></Icon>
