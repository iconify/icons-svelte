<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azh1nvbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azh1nvbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tool" {...props}></Icon>
