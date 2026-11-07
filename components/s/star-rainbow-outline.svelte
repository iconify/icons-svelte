<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er7-pbg8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er7-pbg8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-rainbow-outline" {...props}></Icon>
