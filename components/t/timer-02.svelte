<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp2ocqb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp2ocqb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:timer-02" {...props}></Icon>
