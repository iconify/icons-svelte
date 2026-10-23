<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmth4cbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmth4cbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-percent" {...props}></Icon>
