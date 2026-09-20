<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxdm9zbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxdm9zbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tab-minus" {...props}></Icon>
