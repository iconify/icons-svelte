<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg_1ndbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rg_1ndbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sunset-fill" {...props}></Icon>
