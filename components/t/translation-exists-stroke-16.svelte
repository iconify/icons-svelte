<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twl3sac9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="twl3sac9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-exists-stroke-16" {...props}></Icon>
