<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzk_pozbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzk_pozbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-radius" {...props}></Icon>
