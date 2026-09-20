<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb7lxbc2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb7lxbc2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:star" {...props}></Icon>
