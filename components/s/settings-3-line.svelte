<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tekxwr7wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tekxwr7wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-3-line" {...props}></Icon>
