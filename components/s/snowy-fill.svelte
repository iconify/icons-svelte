<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkjgbnxno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkjgbnxno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:snowy-fill" {...props}></Icon>
