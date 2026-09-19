<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htry_vb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":477,"height":512};
const content = `<path class="htry_vb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:yarn" {...props}></Icon>
