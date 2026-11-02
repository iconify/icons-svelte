<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpkh63bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpkh63bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowman-line" {...props}></Icon>
