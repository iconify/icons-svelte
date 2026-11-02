<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqbe3v_5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqbe3v_5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sandstorm-line" {...props}></Icon>
