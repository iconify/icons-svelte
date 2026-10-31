<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw5lxubtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw5lxubtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dot-round" {...props}></Icon>
