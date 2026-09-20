<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyf_p3b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyf_p3b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:run-line" {...props}></Icon>
