<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miphzu53b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miphzu53b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:trader-joes" {...props}></Icon>
