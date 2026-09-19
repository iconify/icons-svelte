<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orz84zbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orz84zbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:split-filled" {...props}></Icon>
