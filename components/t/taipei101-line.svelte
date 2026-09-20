<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfmc3nbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfmc3nbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taipei101-line" {...props}></Icon>
