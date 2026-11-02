<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5mc_5_lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5mc_5_lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taipei101-fill" {...props}></Icon>
