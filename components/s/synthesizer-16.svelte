<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh3pbsbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jh3pbsbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:synthesizer-16" {...props}></Icon>
