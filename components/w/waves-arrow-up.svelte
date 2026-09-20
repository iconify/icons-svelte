<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub1plsr2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub1plsr2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:waves-arrow-up" {...props}></Icon>
