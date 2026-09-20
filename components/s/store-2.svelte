<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5xa68byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5xa68byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:store-2" {...props}></Icon>
