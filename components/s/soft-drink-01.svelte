<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2m05ta2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2m05ta2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:soft-drink-01" {...props}></Icon>
