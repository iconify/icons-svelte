<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0ei4q6_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0ei4q6_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:seat" {...props}></Icon>
