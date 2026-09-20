<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va893noiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va893noiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:san-francisco-municipal-railway" {...props}></Icon>
