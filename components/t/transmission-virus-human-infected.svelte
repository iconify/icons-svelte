<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clkb5-fug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clkb5-fug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-human-infected" {...props}></Icon>
