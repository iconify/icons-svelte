<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sibgfifdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sibgfifdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:satoshi-v1-outline" {...props}></Icon>
