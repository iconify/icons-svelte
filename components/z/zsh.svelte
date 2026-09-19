<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrqf8_bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrqf8_bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:zsh" {...props}></Icon>
