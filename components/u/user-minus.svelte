<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in61ghe1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in61ghe1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-minus" {...props}></Icon>
