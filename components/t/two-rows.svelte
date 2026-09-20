<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpurzkbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpurzkbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:two-rows" {...props}></Icon>
