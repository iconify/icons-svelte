<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgcdr68to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgcdr68to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick-minus" {...props}></Icon>
