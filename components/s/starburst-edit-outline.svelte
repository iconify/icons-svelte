<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iig1kgbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iig1kgbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:starburst-edit-outline" {...props}></Icon>
