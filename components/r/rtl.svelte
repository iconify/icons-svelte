<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awmzn4b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awmzn4b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rtl" {...props}></Icon>
