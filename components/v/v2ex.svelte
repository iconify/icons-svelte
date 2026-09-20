<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze__gra_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze__gra_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:v2ex" {...props}></Icon>
