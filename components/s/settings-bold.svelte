<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bklevro9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bklevro9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:settings-bold" {...props}></Icon>
