<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwp02941m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwp02941m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:xing" {...props}></Icon>
