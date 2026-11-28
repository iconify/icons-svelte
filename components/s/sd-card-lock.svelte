<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uulq3c4ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uulq3c4ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sd-card-lock" {...props}></Icon>
