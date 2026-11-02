<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boi4y04jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boi4y04jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-left-fill" {...props}></Icon>
