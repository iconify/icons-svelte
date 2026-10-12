<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzy3_p34v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzy3_p34v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-two-columns" {...props}></Icon>
