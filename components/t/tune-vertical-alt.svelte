<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd-wl6bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd-wl6bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tune-vertical-alt" {...props}></Icon>
