<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyu8w92ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyu8w92ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:samsclub" {...props}></Icon>
