<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cimaenb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cimaenb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-fill" {...props}></Icon>
