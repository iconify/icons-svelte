<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf081acuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf081acuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:unsplash" {...props}></Icon>
