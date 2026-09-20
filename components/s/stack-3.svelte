<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg7s-f8zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg7s-f8zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stack-3" {...props}></Icon>
