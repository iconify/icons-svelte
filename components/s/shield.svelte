<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9d61z38w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9d61z38w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:shield" {...props}></Icon>
