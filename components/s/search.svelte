<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isk5td_we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isk5td_we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search" {...props}></Icon>
