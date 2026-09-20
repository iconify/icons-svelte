<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8hdvzblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="u8hdvzblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:volume-up-circle-f" {...props}></Icon>
