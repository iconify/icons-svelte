<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2yw4w_ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2yw4w_ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zsh" {...props}></Icon>
