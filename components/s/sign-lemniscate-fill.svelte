<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7ws10x5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7ws10x5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-lemniscate-fill" {...props}></Icon>
