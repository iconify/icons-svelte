<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td5fekbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="td5fekbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slash-circle-bold" {...props}></Icon>
