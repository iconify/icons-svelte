<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3kj2qixg.css';
import '../../css/w/wygmz5bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3kj2qixg"/><path class="wygmz5bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-down-right-enter-filled" {...props}></Icon>
