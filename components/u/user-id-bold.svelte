<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfwtoyb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jfwtoyb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-id-bold" {...props}></Icon>
