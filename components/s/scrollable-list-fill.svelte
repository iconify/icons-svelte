<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3e1-4bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3e1-4bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scrollable-list-fill" {...props}></Icon>
