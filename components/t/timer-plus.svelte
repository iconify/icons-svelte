<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbgip-g1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbgip-g1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:timer-plus" {...props}></Icon>
