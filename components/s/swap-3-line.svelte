<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehzb5827t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehzb5827t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:swap-3-line" {...props}></Icon>
