<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh4teh6rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh4teh6rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shapes" {...props}></Icon>
