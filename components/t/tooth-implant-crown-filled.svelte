<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri88sebtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ri88sebtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-implant-crown-filled" {...props}></Icon>
