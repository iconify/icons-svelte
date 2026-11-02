<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyspgxbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyspgxbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yoga-line" {...props}></Icon>
