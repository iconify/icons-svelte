<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwsils6ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwsils6ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yahoo-fill" {...props}></Icon>
