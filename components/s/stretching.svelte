<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huk7mmbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huk7mmbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stretching" {...props}></Icon>
