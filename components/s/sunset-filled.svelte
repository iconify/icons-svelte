<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho9s2xbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho9s2xbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sunset-filled" {...props}></Icon>
