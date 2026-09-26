<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-mrvim6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-mrvim6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sd-card-outline" {...props}></Icon>
