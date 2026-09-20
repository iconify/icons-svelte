<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h78-_kb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h78-_kb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:suitcase-fill" {...props}></Icon>
