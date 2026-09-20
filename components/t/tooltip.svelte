<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqohh9f6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqohh9f6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:tooltip" {...props}></Icon>
