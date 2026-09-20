<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svo0q69nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svo0q69nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-down" {...props}></Icon>
