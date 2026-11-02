<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctc1llh8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctc1llh8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:subtitle-fill" {...props}></Icon>
