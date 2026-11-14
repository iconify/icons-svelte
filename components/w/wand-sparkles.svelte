<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng2jmjb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng2jmjb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wand-sparkles" {...props}></Icon>
