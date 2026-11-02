<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao5qlj_ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao5qlj_ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:webhook-fill" {...props}></Icon>
