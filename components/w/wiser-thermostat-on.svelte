<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/catqbqw_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="catqbqw_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wiser-thermostat-on" {...props}></Icon>
