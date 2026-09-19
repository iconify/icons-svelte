<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h842pnhxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h842pnhxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sparkle-circle-filled" {...props}></Icon>
