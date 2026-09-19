<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th7y1ob8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th7y1ob8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:threads" {...props}></Icon>
