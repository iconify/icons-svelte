<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bauv5ofyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bauv5ofyh primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-off-duotone" {...props}></Icon>
