<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln8kehb4v.css';
import '../../css/h/hz4g9vbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ln8kehb4v"/><path class="hz4g9vbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-speaker" {...props}></Icon>
