<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcumr__tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcumr__tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sun-off" {...props}></Icon>
