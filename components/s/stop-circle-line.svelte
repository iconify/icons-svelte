<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzsr9gn5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzsr9gn5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stop-circle-line" {...props}></Icon>
