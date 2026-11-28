<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9pbffbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9pbffbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-cog-solid" {...props}></Icon>
