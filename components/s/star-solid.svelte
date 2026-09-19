<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu9n9sbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu9n9sbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:star-solid" {...props}></Icon>
