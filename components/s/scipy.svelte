<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la2deubsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la2deubsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:scipy" {...props}></Icon>
