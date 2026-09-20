<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hza_l0bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hza_l0bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sticky-note-line" {...props}></Icon>
