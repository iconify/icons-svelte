<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2k-xccia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2k-xccia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:super-intelligence-file" {...props}></Icon>
