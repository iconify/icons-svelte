<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4hmsdbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f4hmsdbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-exists-fill-16" {...props}></Icon>
