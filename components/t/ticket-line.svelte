<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaqxp6zrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaqxp6zrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ticket-line" {...props}></Icon>
