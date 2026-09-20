<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6l25-o4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6l25-o4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-outline" {...props}></Icon>
