<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlj6oovbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlj6oovbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sausage-filled" {...props}></Icon>
