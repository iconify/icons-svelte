<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6q-x2b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6q-x2b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:version-fill" {...props}></Icon>
