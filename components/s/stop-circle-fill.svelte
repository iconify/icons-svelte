<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u27b7vd_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u27b7vd_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:stop-circle-fill" {...props}></Icon>
