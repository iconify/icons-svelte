<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_amfe9of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_amfe9of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:run-2-line" {...props}></Icon>
