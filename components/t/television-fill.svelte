<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-t5h85bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-t5h85bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:television-fill" {...props}></Icon>
