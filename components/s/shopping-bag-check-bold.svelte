<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu2tw4bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu2tw4bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-bag-check-bold" {...props}></Icon>
