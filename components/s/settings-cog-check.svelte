<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b88-1hbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b88-1hbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:settings-cog-check" {...props}></Icon>
