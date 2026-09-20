<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imtb1zu4x.css';
import '../../css/n/nhxejibsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imtb1zu4x"/><path class="nhxejibsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowstorm-2-fill" {...props}></Icon>
