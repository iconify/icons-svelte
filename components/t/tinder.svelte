<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh-8-v7nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh-8-v7nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tinder" {...props}></Icon>
