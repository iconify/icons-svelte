<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg414d5aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg414d5aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slash-commands-2" {...props}></Icon>
