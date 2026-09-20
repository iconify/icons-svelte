<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rovq1db4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rovq1db4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shield-shape-fill" {...props}></Icon>
