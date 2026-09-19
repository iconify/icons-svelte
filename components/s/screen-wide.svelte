<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygd9qibvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygd9qibvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:screen-wide" {...props}></Icon>
