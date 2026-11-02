<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vugvi1nbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vugvi1nbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terror-fill" {...props}></Icon>
