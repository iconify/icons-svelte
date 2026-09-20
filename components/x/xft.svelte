<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4j-ds-3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4j-ds-3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xft" {...props}></Icon>
