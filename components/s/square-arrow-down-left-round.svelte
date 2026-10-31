<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbsj4lbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbsj4lbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-down-left-round" {...props}></Icon>
