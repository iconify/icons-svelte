<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq_8t4b0z.css';
import '../../css/e/ef96-hbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jq_8t4b0z"/><path class="ef96-hbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terminal-20" {...props}></Icon>
