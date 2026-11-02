<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvim2ibiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvim2ibiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-fill" {...props}></Icon>
