<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw25wivmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vw25wivmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:wayside-shrine" {...props}></Icon>
