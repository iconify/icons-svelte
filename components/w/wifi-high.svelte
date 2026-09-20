<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-pq1rbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-pq1rbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wifi-high" {...props}></Icon>
