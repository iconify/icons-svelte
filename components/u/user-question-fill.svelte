<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnhckg2ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnhckg2ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-question-fill" {...props}></Icon>
