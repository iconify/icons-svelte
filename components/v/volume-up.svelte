<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-cu9tb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="q-cu9tb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:volume-up" {...props}></Icon>
