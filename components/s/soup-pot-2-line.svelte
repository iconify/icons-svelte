<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu4p4krzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu4p4krzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:soup-pot-2-line" {...props}></Icon>
