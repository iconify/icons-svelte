<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb5i6giuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb5i6giuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-cancel" {...props}></Icon>
