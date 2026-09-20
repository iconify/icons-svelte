<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-d--rbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-d--rbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-7-line" {...props}></Icon>
