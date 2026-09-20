<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg4wgjwlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg4wgjwlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:yaml" {...props}></Icon>
