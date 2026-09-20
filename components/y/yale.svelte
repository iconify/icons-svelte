<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9uyf0_qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9uyf0_qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yale" {...props}></Icon>
