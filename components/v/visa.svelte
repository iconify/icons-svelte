<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih3jvg44a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih3jvg44a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:visa" {...props}></Icon>
