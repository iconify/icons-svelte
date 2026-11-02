<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j62blcc0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j62blcc0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-align-end-line" {...props}></Icon>
