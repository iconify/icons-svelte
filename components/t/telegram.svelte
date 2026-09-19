<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o77g2cbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o77g2cbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:telegram" {...props}></Icon>
