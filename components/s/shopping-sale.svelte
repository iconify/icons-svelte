<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtx8_905u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtx8_905u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-sale" {...props}></Icon>
