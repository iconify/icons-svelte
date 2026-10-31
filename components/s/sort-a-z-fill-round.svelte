<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5liy5rbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5liy5rbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sort-a-z-fill-round" {...props}></Icon>
