<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjajlikcf.css';
import '../../css/q/q4b6bxbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sjajlikcf"/><path class="q4b6bxbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:train-fill" {...props}></Icon>
