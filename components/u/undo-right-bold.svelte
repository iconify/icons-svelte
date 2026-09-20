<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caoutqb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="caoutqb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-right-bold" {...props}></Icon>
