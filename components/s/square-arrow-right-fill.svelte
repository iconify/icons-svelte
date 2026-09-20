<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhae8twzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhae8twzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-right-fill" {...props}></Icon>
