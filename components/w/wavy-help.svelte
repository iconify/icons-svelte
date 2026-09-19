<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfcvgv5ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfcvgv5ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:wavy-help" {...props}></Icon>
