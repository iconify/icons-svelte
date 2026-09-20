<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca060d3pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca060d3pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:strategy-tasks-remix" {...props}></Icon>
