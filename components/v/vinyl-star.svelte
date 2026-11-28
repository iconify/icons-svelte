<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr1motb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr1motb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:vinyl-star" {...props}></Icon>
