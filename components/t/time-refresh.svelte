<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-zr0lbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-zr0lbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:time-refresh" {...props}></Icon>
