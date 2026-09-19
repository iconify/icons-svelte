<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htl8_ibad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htl8_ibad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:shopping-bag-01" {...props}></Icon>
