<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo937_3bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo937_3bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:shortcut" {...props}></Icon>
