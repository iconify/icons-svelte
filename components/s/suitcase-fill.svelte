<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmo9kkbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmo9kkbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:suitcase-fill" {...props}></Icon>
