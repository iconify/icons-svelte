<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxmrc6bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxmrc6bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:stimulus" {...props}></Icon>
