<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u09kphb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u09kphb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-4-fill" {...props}></Icon>
