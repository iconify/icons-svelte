<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmxt5nb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmxt5nb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-4-fill" {...props}></Icon>
