<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urcr01bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urcr01bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:table" {...props}></Icon>
