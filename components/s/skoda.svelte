<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttzi-7b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttzi-7b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:skoda" {...props}></Icon>
