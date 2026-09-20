<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar77dfhjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar77dfhjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:samsung" {...props}></Icon>
