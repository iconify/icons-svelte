<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kij4pmdra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kij4pmdra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:trend-down" {...props}></Icon>
