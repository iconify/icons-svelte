<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sujsk-bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sujsk-bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:text-formating-arrange-spacing" {...props}></Icon>
