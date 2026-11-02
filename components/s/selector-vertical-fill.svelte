<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he2h3cb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he2h3cb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:selector-vertical-fill" {...props}></Icon>
