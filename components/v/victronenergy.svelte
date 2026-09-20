<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwly73l6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwly73l6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:victronenergy" {...props}></Icon>
