<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idh6qysuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idh6qysuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:to-do-fill" {...props}></Icon>
