<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2fzirb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2fzirb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tent-off" {...props}></Icon>
