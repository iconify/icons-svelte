<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-06obvoh.css';
import '../../css/l/ly4zvcbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-06obvoh"/><path class="ly4zvcbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-1-line" {...props}></Icon>
