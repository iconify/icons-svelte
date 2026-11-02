<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oih2r0kjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oih2r0kjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-bag-2-fill" {...props}></Icon>
