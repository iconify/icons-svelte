<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntffnhbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntffnhbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:user-minus" {...props}></Icon>
