<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc87gqb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc87gqb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:store-sharp" {...props}></Icon>
