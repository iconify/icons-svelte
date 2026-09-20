<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm3c22buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm3c22buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:swisscows" {...props}></Icon>
