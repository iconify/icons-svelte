<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3v50cb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3v50cb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:structure-bold" {...props}></Icon>
