<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-zvj7b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-zvj7b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tree-4-fill" {...props}></Icon>
