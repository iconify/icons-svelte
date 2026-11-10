<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi_b2-t-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi_b2-t-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:translate" {...props}></Icon>
