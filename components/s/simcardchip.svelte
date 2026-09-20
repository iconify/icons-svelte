<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3un0yblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="u3un0yblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:simcardchip" {...props}></Icon>
