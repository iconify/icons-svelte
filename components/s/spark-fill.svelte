<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg90yx5_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg90yx5_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:spark-fill" {...props}></Icon>
