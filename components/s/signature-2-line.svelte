<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slnehab3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slnehab3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:signature-2-line" {...props}></Icon>
