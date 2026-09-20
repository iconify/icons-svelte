<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usdhhe98m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usdhhe98m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wrld" {...props}></Icon>
