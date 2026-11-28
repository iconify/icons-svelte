<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw9k-nbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw9k-nbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tent" {...props}></Icon>
