<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-6mscczn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-6mscczn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spacing-vertical-line" {...props}></Icon>
