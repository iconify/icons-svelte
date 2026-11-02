<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ersehub6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ersehub6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-4-line" {...props}></Icon>
