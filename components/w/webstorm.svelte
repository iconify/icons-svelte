<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjm_-zaob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjm_-zaob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:webstorm" {...props}></Icon>
