<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyzybgk3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyzybgk3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:thunderstorm-strong-filled" {...props}></Icon>
