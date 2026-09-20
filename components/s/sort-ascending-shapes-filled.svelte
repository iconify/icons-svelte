<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwy2_jbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwy2_jbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-ascending-shapes-filled" {...props}></Icon>
