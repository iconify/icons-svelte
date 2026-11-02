<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4_guibpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4_guibpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:train-3-line" {...props}></Icon>
