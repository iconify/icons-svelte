<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4saz8bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4saz8bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:user-check" {...props}></Icon>
