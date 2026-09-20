<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cro202h0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cro202h0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:srgssr" {...props}></Icon>
