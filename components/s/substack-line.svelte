<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okku99b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okku99b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:substack-line" {...props}></Icon>
