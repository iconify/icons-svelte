<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8_7469hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8_7469hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:siren-alt-filled" {...props}></Icon>
