<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgn5mabhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgn5mabhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trouser-fill" {...props}></Icon>
