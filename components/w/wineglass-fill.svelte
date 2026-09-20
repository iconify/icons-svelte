<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hky1e_bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hky1e_bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wineglass-fill" {...props}></Icon>
