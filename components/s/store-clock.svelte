<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqv6wq04x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqv6wq04x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:store-clock" {...props}></Icon>
