<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf0xxccbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf0xxccbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:text-quote-solid" {...props}></Icon>
