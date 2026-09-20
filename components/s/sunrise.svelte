<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl3o0g27x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl3o0g27x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sunrise" {...props}></Icon>
