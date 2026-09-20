<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5_simimr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l5_simimr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:terminal" {...props}></Icon>
