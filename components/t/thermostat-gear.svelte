<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c42l-0b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c42l-0b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:thermostat-gear" {...props}></Icon>
