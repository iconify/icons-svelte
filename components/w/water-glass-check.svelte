<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv1_vybbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv1_vybbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:water-glass-check" {...props}></Icon>
