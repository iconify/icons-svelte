<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqawakj1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqawakj1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sandglass-2-line" {...props}></Icon>
