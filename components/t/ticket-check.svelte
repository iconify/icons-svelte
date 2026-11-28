<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkj9vcbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkj9vcbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ticket-check" {...props}></Icon>
