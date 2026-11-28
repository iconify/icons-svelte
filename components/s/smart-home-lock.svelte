<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amn23owsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amn23owsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smart-home-lock" {...props}></Icon>
