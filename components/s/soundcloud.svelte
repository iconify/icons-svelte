<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd8h6cc5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8h6cc5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:soundcloud" {...props}></Icon>
