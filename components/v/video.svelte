<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ajjh6kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ajjh6kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:video" {...props}></Icon>
