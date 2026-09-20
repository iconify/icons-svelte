<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6cd_92qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6cd_92qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:textformat-italic" {...props}></Icon>
