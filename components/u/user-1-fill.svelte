<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqi00l9tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqi00l9tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-1-fill" {...props}></Icon>
