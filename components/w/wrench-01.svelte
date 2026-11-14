<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3c8y6bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3c8y6bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wrench-01" {...props}></Icon>
