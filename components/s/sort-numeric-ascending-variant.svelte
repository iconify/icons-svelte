<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp2ge7b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp2ge7b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-numeric-ascending-variant" {...props}></Icon>
