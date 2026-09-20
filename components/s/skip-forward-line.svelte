<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok38s20xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok38s20xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:skip-forward-line" {...props}></Icon>
