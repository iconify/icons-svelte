<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee7w3zqxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee7w3zqxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scrollable-list-fill" {...props}></Icon>
