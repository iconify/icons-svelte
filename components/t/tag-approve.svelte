<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-5jx4blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-5jx4blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-approve" {...props}></Icon>
