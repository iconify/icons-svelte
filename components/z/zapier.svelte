<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0entlbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0entlbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zapier" {...props}></Icon>
