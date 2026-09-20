<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4kwoob5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4kwoob5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-head-focus-remix" {...props}></Icon>
