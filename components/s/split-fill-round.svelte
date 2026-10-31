<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5n2a1blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5n2a1blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:split-fill-round" {...props}></Icon>
