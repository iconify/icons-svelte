<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi4o4ac1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi4o4ac1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sos" {...props}></Icon>
