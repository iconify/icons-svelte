<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k20jmtbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k20jmtbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:suitcase-2-line" {...props}></Icon>
