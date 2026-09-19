<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrcefkb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrcefkb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:timer-cancel-filled" {...props}></Icon>
