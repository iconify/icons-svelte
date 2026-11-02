<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n98i4bxrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n98i4bxrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-lock-fill" {...props}></Icon>
