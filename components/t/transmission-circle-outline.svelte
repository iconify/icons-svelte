<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b71j5xfyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b71j5xfyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transmission-circle-outline" {...props}></Icon>
