<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm82tsche.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm82tsche"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sticky-note-filled" {...props}></Icon>
