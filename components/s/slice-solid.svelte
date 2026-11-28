<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rboqugqqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rboqugqqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:slice-solid" {...props}></Icon>
