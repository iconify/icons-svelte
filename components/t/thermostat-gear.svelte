<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/potmh-1wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="potmh-1wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:thermostat-gear" {...props}></Icon>
