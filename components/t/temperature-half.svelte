<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku-h9g-aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku-h9g-aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:temperature-half" {...props}></Icon>
