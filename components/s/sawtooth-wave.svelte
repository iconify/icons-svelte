<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9knjwb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9knjwb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sawtooth-wave" {...props}></Icon>
