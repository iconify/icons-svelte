<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg6v3mbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg6v3mbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-circle-check" {...props}></Icon>
